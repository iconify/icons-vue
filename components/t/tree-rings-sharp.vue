<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="obbquibit"/><path class="b8e-6zb0w"/><path class="shtca1b1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-rings-sharp" /></template>
<style>
.b8e-6zb0w {
  d: path("M6 12.5a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

.obbquibit {
  d: path("m12.95 3.07l.81.28q.94.33 1.86.73l1 .43l.92.4l-.31.95l-.14.42l-.32.95l.95-.32l.42-.14l.95-.31l.54.84l.63 1l.54.84l-.02 1l-.01.86q-.02 1 0 2l.01.86l.02 1l-.6.8l-.52.68q-.6.8-1.18 1.62l-.49.7l-.57.82l-.96.3l-.82.25q-.96.29-1.9.62l-.81.28l-.95.32l-.95-.32l-.81-.28q-.94-.33-1.9-.62l-.82-.25l-.96-.3l-.57-.82l-.49-.7q-.58-.82-1.18-1.62l-.52-.68l-.6-.8l.02-1l.01-.86q.02-1 0-2l-.01-.86l-.02-1l.6-.8l.52-.68q.6-.8 1.18-1.62l.49-.7l.57-.82l.96-.3l.82-.25q.96-.29 1.9-.62l.81-.28l.95-.32z");
}

.shtca1b1b {
  d: path("M8.9 12.85a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
