<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6uzf-99s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6uzf-99s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:move-diagonal-right" /></template>
