<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4f_v4gza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p4f_v4gza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zen" /></template>
