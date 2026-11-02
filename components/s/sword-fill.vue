<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kss_nj_le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kss_nj_le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sword-fill" /></template>
