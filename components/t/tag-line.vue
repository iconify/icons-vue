<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg3c--bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg3c--bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:tag-line" /></template>
