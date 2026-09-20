<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s58i6g_jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s58i6g_jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:upload-1" /></template>
