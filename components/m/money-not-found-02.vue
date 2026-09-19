<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jc_7zfapj.css';
import '../../css/w/wber-hsua.css';
import '../../css/o/ope6mwbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jc_7zfapj"/><path class="wber-hsua"/><path class="ope6mwbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-not-found-02" /></template>
