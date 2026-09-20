<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sku5yxboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sku5yxboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speaker-fill" /></template>
