<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="csnh2ergs"/><path class="clsqbwb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tent-duotone" /></template>
<style>
.clsqbwb1n {
  d: path("M11 22.0001L11 12.3895C11 11.8372 11.4477 11.3895 12 11.3895C12.3892 11.3895 12.743 11.6153 12.9069 11.9682L17.5672 22.0001L11 22.0001Z");
}

.csnh2ergs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.3619 20.0001L10.1862 3.1573C10.4044 2.6815 10.802 2.3114 11.2923 2.1278C11.5187 2.0433 11.7583 2 12 2C12.2417 2 12.4813 2.0433 12.7077 2.1278C13.198 2.3114 13.5956 2.6815 13.8138 3.1573L21.6381 20.0001L22 20.0001C22.5523 20.0001 23 20.4478 23 21.0001C23 21.5524 22.5523 22.0001 22 22.0001L2 22.0001C1.4477 22.0001 1 21.5524 1 21.0001C1 20.4478 1.4477 20.0001 2 20.0001L2.3619 20.0001Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
