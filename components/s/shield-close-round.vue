<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn-6sfbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn-6sfbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-close-round" /></template>
