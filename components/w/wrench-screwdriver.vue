<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zarq2obis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zarq2obis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wrench-screwdriver" /></template>
