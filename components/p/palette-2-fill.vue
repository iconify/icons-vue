<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbrnx5bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbrnx5bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-2-fill" /></template>
