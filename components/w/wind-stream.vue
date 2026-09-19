<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmwis782f.css';
import '../../css/j/j52z7pbtj.css';
import '../../css/c/chhmubb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cmwis782f"/><path class="j52z7pbtj"/><path class="chhmubb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wind-stream" /></template>
