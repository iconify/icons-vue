<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khi8ekbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khi8ekbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sort-ascending-line" /></template>
