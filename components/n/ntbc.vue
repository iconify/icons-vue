<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs__h_6vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hs__h_6vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ntbc" /></template>
