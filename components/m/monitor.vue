<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iizu05bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="iizu05bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:monitor" /></template>
