<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2mh2_bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t2mh2_bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:router-voice" /></template>
