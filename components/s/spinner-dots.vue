<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2l0wwb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2l0wwb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:spinner-dots" /></template>
