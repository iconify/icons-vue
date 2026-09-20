<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjo4cywis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjo4cywis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-furniture" /></template>
