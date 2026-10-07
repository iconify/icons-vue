<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wzmu56b-h.css';
import '../../css/b/b64l0dbmf.css';
import '../../css/j/jkon69jfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzmu56b-h"/><path class="b64l0dbmf"/><path class="jkon69jfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rotate-camera-left" /></template>
