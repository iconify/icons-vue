<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r6d8msbmx"/><path clip-rule="evenodd" class="pvvuwc89a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sports-court-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pvvuwc89a {
  fill-rule: evenodd;
  d: path("M13 3V4V9.171C14.165 9.582 15 10.694 15 12C15 12.828 14.663 13.58 14.121 14.121C13.809 14.434 13.427 14.678 13 14.829V20V21H11V20V14.829C9.835 14.417 9 13.306 9 12C9 10.694 9.835 9.582 11 9.171V4V3H12H13ZM1 7H2H6C6.552 7 7 7.448 7 8V16C7 16.552 6.552 17 6 17H2H1V15H2H5V9H2H1V7ZM23 9H22H19V15H22H23V17H22H18C17.448 17 17 16.552 17 16V8C17 7.448 17.448 7 18 7H22H23V9ZM12.707 12.707C12.889 12.525 13 12.276 13 12C13 11.448 12.552 11 12 11C11.448 11 11 11.448 11 12C11 12.552 11.448 13 12 13C12.276 13 12.525 12.889 12.707 12.707Z");
}

.r6d8msbmx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3H22C22.552 3 23 3.448 23 4V20C23 20.552 22.552 21 22 21H2C1.448 21 1 20.552 1 20V4C1 3.448 1.448 3 2 3H12Z");
}

</style>
