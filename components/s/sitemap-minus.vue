<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ril2l8bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ril2l8bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sitemap-minus" /></template>
