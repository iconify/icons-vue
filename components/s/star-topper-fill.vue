<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq0x9-boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq0x9-boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-topper-fill" /></template>
