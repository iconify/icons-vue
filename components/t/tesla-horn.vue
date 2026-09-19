<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncb6-0bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncb6-0bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-horn" /></template>
