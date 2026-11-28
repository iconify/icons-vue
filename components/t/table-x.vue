<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqf7kkdmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqf7kkdmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:table-x" /></template>
