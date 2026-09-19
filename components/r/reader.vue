<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn8ho2_yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn8ho2_yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader" /></template>
