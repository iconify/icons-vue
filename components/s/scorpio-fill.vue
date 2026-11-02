<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-d24bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny-d24bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scorpio-fill" /></template>
