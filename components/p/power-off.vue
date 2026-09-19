<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tytm7lt4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="tytm7lt4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:power-off" /></template>
