<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx8_exglu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yx8_exglu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamtx-dark" /></template>
