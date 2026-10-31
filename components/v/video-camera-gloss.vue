<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk_is3nbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk_is3nbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-camera-gloss" /></template>
