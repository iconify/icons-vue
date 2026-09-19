<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-ue3xmcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="s-ue3xmcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:superpowers" /></template>
