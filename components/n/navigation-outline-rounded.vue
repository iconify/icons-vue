<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3ah20bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:navigation-outline-rounded" /></template>
<style>
.g3ah20bpm {
  fill: currentColor;
  d: path("m12 16.923l-4.95 2.116q-.267.105-.497.043q-.23-.063-.392-.224t-.224-.404t.063-.49l5.267-11.837q.106-.243.311-.364q.205-.12.422-.12t.422.12t.31.364L18 17.964q.125.248.063.49q-.063.242-.224.404t-.392.224t-.497-.044zm-4.9.977l4.9-2.1l4.9 2.1l-4.9-11zm4.9-2.1");
}

</style>
