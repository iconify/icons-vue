<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrdhdlbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrdhdlbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:milk-line" /></template>
