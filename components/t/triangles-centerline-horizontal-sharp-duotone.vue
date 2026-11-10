<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oovjecb9h"/><path class="r_-4hoblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-horizontal-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oovjecb9h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.292 15C16.609 15.04 16.992 15.31 17.142 15.6C17.249 15.9 17.228 16.31 17.041 16.58L12.818 22.58C12.655 22.81 12.344 22.97 12.065 23C11.74 23 11.37 22.84 11.183 22.58L6.96 16.58C6.746 16.27 6.752 15.81 6.921 15.48C7.108 15.22 7.452 15 7.777 15H16.292ZM11.935 1C12.26 1 12.631 1.16 12.818 1.42L17.041 7.42C17.228 7.69 17.249 8.1 17.142 8.4C16.992 8.69 16.609 8.96 16.292 9H7.777C7.492 9 7.13 8.77 6.943 8.57C6.775 8.24 6.747 7.73 6.96 7.42L11.182 1.42C11.345 1.19 11.657 1.03 11.935 1Z");
}

.r_-4hoblq {
  d: path("M23 11V13H1V11H23Z");
}

</style>
