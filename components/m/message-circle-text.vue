<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knp8ggb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knp8ggb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-text" /></template>
