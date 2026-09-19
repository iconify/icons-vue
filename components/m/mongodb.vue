<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzr_vydyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hzr_vydyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mongodb" /></template>
