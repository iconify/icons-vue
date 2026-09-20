<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuw1tfb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuw1tfb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-filter" /></template>
