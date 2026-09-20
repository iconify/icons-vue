<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul4-oqb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4-oqb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:suitcase-2-line" /></template>
