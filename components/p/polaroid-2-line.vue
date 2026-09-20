<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgp-hdafg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgp-hdafg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:polaroid-2-line" /></template>
