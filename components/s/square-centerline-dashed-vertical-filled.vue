<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8qrl_cai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8qrl_cai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-centerline-dashed-vertical-filled" /></template>
