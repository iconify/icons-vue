<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojp61_uzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojp61_uzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-none-fill" /></template>
