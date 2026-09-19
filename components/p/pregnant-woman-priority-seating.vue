<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj6zyvo6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj6zyvo6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:pregnant-woman-priority-seating" /></template>
