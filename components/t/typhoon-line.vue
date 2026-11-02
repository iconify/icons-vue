<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p68jygbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p68jygbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:typhoon-line" /></template>
