<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xubakwdyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xubakwdyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:syringe-line" /></template>
