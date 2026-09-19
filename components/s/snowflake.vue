<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scjnt3k6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="scjnt3k6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:snowflake" /></template>
