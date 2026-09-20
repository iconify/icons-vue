<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exojeibni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exojeibni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rss-fill" /></template>
