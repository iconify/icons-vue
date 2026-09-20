<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/kuc5c_btk.css';
import '../../css/j/jmdah2bcp.css';
import '../../css/v/v-ajdhbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kuc5c_btk"/><path class="jmdah2bcp"/><path class="v-ajdhbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-time" /></template>
