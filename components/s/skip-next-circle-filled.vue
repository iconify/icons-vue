<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrizf2d8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrizf2d8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skip-next-circle-filled" /></template>
