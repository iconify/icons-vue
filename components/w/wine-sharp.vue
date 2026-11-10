<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gch5nm0hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wine-sharp" /></template>
<style>
.gch5nm0hh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16H14.414C15.406 16 16.372 15.67 17.165 15.07C18.781 13.84 19.414 11.68 18.724 9.76L15.943 2H8.057L5.276 9.76C4.586 11.68 5.219 13.84 6.834 15.07C7.628 15.67 8.593 16 9.586 16H12ZM12 16V22M12 22H8.043M12 22H15.957M5.548 9H6.084C6.861 9 7.617 8.87 8.238 8.64C8.86 8.4 9.616 8.28 10.393 8.28C11.169 8.28 11.926 8.4 12.547 8.64C13.168 8.87 13.924 9 14.701 9C16.061 9 17.304 8.61 17.913 8L18.045 7.87");
}

</style>
