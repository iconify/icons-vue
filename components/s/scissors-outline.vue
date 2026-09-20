<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kib3_7b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kib3_7b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:scissors-outline" /></template>
