<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agduo96pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agduo96pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wine-glass-alt" /></template>
