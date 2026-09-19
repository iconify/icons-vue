<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8pppjojd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l8pppjojd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:realm" /></template>
