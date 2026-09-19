<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww4fyqbuj.css';
import '../../css/h/hu3x240rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="hu3x240rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning" /></template>
