<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-b8subje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-b8subje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:row-resize" /></template>
