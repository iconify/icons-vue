<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adqshw3kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adqshw3kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:protocol" /></template>
