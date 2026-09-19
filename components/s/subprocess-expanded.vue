<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2l13g56y.css';
import '../../css/y/yu9v0h85x.css';
import '../../css/i/i0e1ugb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<g transform="translate(0 995.638)"><path class="n2l13g56y"/><path class="yu9v0h85x"/><rect class="i0e1ugb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:subprocess-expanded" /></template>
