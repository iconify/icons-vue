<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8hmt80gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8hmt80gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-fill-round" /></template>
