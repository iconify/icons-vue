<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8cjv2wev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8cjv2wev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-yuan-filled" /></template>
