<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me-uzgbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me-uzgbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:virus-gloss" /></template>
