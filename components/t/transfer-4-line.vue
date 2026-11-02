<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyysn4b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyysn4b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-4-line" /></template>
