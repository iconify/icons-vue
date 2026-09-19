<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_1hu37k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_1hu37k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:signe-gradient-table" /></template>
