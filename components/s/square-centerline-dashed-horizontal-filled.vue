<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3df__o1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3df__o1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-centerline-dashed-horizontal-filled" /></template>
