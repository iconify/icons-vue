<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckhmp3bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckhmp3bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:move-horizontal" /></template>
