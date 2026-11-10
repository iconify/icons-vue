<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz2l9yb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:salad-sharp" /></template>
<style>
.vz2l9yb0l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13H2C3.052 17.68 7.206 21 12 21M3 13H9M3 13C3 11.34 4.343 10 6 10C7.657 10 9 11.34 9 13M12 21C16.794 21 20.948 17.68 22 13H18.2M12 21H4M12 21H20M9 13H13.203M18.2 13C18.402 12.82 18.595 12.63 18.78 12.43C19.858 11.27 20.582 9.82 20.866 8.26C21.149 6.7 20.981 5.09 20.381 3.62C20.29 3.4 20.12 3.21 19.903 3.11C19.686 3 19.437 2.97 19.203 3.03C17.668 3.43 16.279 4.26 15.201 5.43C14.122 6.59 13.399 8.04 13.115 9.6C12.909 10.73 12.941 11.89 13.203 13M18.2 13H14.956M13.203 13H14.956M14.956 13L17.915 7.08M16.216 4.5L15.755 4.32C13.5 3.4 10.9 3.9 10.2 6.9C8.9 6 6.029 5.87 5 9.73L4.869 10.22");
}

</style>
