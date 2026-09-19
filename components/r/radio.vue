<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha1-zac3l.css';
import '../../css/d/d_11-9bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ha1-zac3l"/><path class="d_11-9bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:radio" /></template>
