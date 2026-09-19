<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ars6nmb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ars6nmb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:spreadsheet" /></template>
