<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxfw2ll-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxfw2ll-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:prisma-orm" /></template>
