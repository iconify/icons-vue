<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiq8g1b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiq8g1b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:math" /></template>
