<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-8y8acqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-8y8acqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sitemap" /></template>
