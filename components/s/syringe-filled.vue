<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn1gikdgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn1gikdgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:syringe-filled" /></template>
