<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idv2q1mcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idv2q1mcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:merge-duotone-round" /></template>
