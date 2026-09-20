<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h1xyzvb4l.css';
import '../../css/b/blphqos8l.css';
import '../../css/f/f1tqfuc1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1xyzvb4l"/><circle class="blphqos8l"/><path class="f1tqfuc1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:msg-bubble-user" /></template>
