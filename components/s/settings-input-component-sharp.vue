<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s29emibag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-input-component-sharp" /></template>
<style>
.s29emibag {
  fill: currentColor;
  d: path("M3.904 22v-4.458L2 15.638v-2.772h4.808v2.773l-1.904 1.903V22zm7.596 0v-4.458L9.596 15.64v-2.773h4.808v2.773L12.5 17.542V22zm7.596 0v-4.458l-1.904-1.903v-2.773H22v2.773l-1.904 1.903V22zM2 11.866V6.173h1.904V2h1v4.173h1.904v5.693zm7.596 0V6.173H11.5V2h1v4.173h1.904v5.693zm7.596 0V6.173h1.904V2h1v4.173H22v5.693z");
}

</style>
