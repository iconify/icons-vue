<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq38d_g_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq38d_g_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:whistle-outline" /></template>
