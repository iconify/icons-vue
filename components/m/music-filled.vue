<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh_10ccvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh_10ccvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music-filled" /></template>
