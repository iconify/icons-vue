<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fgl0cis6t"/><path class="ozgse4b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tent-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fgl0cis6t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.3819 20.0001L11.1056 2.5528C11.275 2.214 11.6212 2 12 2C12.3788 2 12.725 2.214 12.8944 2.5528L21.6181 20.0001L23 20.0001L23 22.0001L1 22.0001L1 20.0001L2.3819 20.0001Z");
}

.ozgse4b5p {
  d: path("M11 22.0001L11 13C11 12.4477 11.4477 12 12 12C12.3788 12 12.725 12.214 12.8944 12.5528L17.6181 22.0001L11 22.0001Z");
}

</style>
