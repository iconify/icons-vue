<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgu11uvkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgu11uvkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:xuanyuan" /></template>
