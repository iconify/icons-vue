<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn-_7ub-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn-_7ub-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:omega" /></template>
