<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/msw74ni7j.css';
import '../../css/e/e4x0wjlqy.css';
import '../../css/z/z1iohkbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msw74ni7j"/><path class="e4x0wjlqy"/><path class="z1iohkbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:yoga" /></template>
