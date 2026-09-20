<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auyq2-22y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auyq2-22y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-question" /></template>
