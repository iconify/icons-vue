<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmdy_eblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmdy_eblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tower-3-fill" /></template>
