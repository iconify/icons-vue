<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmt3mh2kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmt3mh2kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microwave-oven-filled" /></template>
