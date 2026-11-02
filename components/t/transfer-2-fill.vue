<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxb9q8b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxb9q8b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-2-fill" /></template>
