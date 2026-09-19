<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm6s_5b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fm6s_5b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-3" /></template>
