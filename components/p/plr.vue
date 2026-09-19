<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg4gvs8ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zg4gvs8ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:plr" /></template>
