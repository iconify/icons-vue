<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hm0g4b99a.css';
import '../../css/e/e12r68bme.css';
import '../../css/z/zhmxno9se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hm0g4b99a"/><path class="e12r68bme"/><path class="zhmxno9se"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-2-bold" /></template>
