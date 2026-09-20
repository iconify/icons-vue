<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4fr1mber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4fr1mber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:price-tag-3-line" /></template>
