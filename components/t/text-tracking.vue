<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vomyfrboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vomyfrboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-tracking" /></template>
