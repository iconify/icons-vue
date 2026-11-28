<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-2db7ux.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hkbzohbkc.css';
import '../../css/c/cjlrt-g2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-2db7ux secondary"/><g class="dt0cm9dhy primary"><path class="hkbzohbkc"/><path class="cjlrt-g2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-right-split-duo" /></template>
