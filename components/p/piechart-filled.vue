<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkuiw_hnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkuiw_hnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:piechart-filled" /></template>
