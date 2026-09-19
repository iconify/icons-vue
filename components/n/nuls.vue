<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdg1wsjbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sdg1wsjbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nuls" /></template>
