<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7su20_3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7su20_3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:man-filled" /></template>
