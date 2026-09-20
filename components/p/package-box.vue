<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p3g49_bjy.css';
import '../../css/h/hstg4kb0i.css';
import '../../css/d/d-d8bbb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p3g49_bjy"/><path class="hstg4kb0i"/><rect class="d-d8bbb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:package-box" /></template>
