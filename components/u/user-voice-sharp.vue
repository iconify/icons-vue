<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyh-ojaqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-sharp" /></template>
<style>
.eyh-ojaqw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14L10 14C13.3137 14 16 16.6863 16 20L16 21L2 21L2 20C2 16.6863 4.6863 14 8 14ZM9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3431 10 6 8.6569 6 7C6 5.3431 7.3431 4 9 4ZM16.7867 2.4444L17.0623 3C17.6791 4.2432 18 5.6122 18 7C18 8.3878 17.6791 9.7568 17.0623 11L16.7867 11.5556M21.1454 2.3077L21.3693 3C21.7872 4.2922 22 5.6419 22 7C22 9.282 21.3993 11.5238 20.2583 13.5L19.9696 14");
}

</style>
