<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-_jgm2kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-_jgm2kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shop-fill" /></template>
