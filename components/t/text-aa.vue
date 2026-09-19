<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei66cbbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei66cbbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:text-aa" /></template>
