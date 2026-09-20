<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqj36j7ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bqj36j7ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:medrt" /></template>
