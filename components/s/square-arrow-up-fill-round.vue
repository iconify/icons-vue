<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz79s0rdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz79s0rdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-fill-round" /></template>
