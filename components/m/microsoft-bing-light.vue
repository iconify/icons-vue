<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7a2wvbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7a2wvbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-bing-light" /></template>
