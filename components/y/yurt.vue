<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jiaucbm6l.css';
import '../../css/d/dqcj_6b8q.css';
import '../../css/g/g49ywcb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jiaucbm6l"/><path class="dqcj_6b8q"/><path class="g49ywcb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:yurt" /></template>
