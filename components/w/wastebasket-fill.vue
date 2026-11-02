<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz4u7tcag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz4u7tcag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wastebasket-fill" /></template>
