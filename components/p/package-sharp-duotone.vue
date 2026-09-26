<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ewia5rmob"/><path class="di7tu-7tl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.di7tu-7tl {
  d: path("M16.9932 8.3024L21.9863 5.7298L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 7.4574L13 12.6097L13 22.6265L12.4362 22.8998C12.1607 23.0334 11.8393 23.0334 11.5638 22.8998L11 22.6265L11 12.6097L1 7.4574L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L2.0137 5.7298L12 10.8751L14.7906 9.4373L4.7362 4.41L7.0068 3.3093Z");
}

.ewia5rmob {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.4362 1.1002L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 17.1523C23 17.5355 22.781 17.885 22.4362 18.0521L12.4362 22.8998C12.1607 23.0334 11.8393 23.0334 11.5638 22.8998L1.5638 18.0521C1.219 17.885 1 17.5355 1 17.1523L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L11.5638 1.1002C11.8393 0.9666 12.1607 0.9666 12.4362 1.1002Z");
}

</style>
