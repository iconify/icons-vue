<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpmurq.css';
import '../../css/s/so-from-16.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpmurq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:minus" /></template>
