<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqc3k61jp.css';
import '../../css/z/z4lv28bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqc3k61jp"/><path class="z4lv28bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:trash" /></template>
