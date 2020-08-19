<template>
  <div>
    <button class="mb-4 transform hover:scale-125" @click="handleClick">👈
      <span class="text-sm hover:underline">Back</span>
    </button>
  </div>
</template>

<script>
export default {
  name: "BackButton",
  methods: {
    handleClick: function() {
      this.$emit("goBack");
    }
  }
};
</script>
