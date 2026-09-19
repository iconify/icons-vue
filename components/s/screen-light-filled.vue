<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qctaksagg.css';
import '../../css/w/wzczkxivh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="qctaksagg"/><path class="wzczkxivh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:screen-light-filled" /></template>
