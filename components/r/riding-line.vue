<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trqy23_xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trqy23_xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:riding-line" /></template>
