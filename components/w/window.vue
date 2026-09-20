<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/si8xltb9c.css';
import '../../css/n/n3vbv1bpu.css';
import '../../css/a/ahxs4fbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="si8xltb9c"/><path class="n3vbv1bpu"/><path class="ahxs4fbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:window" /></template>
