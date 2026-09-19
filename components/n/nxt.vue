<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bik083bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bik083bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nxt" /></template>
