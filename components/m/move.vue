<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqh5nbc3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqh5nbc3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:move" /></template>
