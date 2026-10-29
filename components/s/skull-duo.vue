<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gg9qschrj.css';
import '../../css/w/w3qnxqbjy.css';
import '../../css/t/tjbgnmb3g.css';
import '../../css/o/oum2fkb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gg9qschrj"/><path class="w3qnxqbjy wm-a"/><path class="tjbgnmb3g"/><path class="oum2fkb0t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:skull-duo" /></template>
