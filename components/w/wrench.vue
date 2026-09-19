<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1p-5-ejl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1p-5-ejl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:wrench" /></template>
