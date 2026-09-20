<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d60hbwahx.css';
import '../../css/c/cnqq36xqp.css';
import '../../css/z/zunq1wbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":120};
const content = `<g class="d60hbwahx"><path clip-rule="evenodd" class="cnqq36xqp"/><path class="zunq1wbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:refine-light" /></template>
