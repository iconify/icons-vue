<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xzntu9doz.css';
import '../../css/e/e12r68bme.css';
import '../../css/g/gn31iacux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xzntu9doz"/><path class="e12r68bme"/><path clip-rule="evenodd" class="gn31iacux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-bold" /></template>
