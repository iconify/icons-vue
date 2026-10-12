<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qygv4bbtf.css';
import '../../css/c/c37msdwqu.css';
import '../../css/j/jh-jfdc-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qygv4bbtf"/><path class="c37msdwqu"/><path class="jh-jfdc-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-check-duotone" /></template>
