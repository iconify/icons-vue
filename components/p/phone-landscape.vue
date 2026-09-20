<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zngyz-aul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="zngyz-aul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:phone-landscape" /></template>
