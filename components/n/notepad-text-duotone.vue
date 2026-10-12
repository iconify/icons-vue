<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oemvd_byo.css';
import '../../css/x/x8rurvb8y.css';
import '../../css/z/zy0239y8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oemvd_byo"/><path class="x8rurvb8y"/><path class="zy0239y8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:notepad-text-duotone" /></template>
