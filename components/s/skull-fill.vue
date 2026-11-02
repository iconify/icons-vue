<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6k_tobqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6k_tobqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skull-fill" /></template>
