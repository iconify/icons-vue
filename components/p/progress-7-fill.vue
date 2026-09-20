<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i64g3g2nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i64g3g2nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-7-fill" /></template>
