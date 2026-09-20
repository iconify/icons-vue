<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o12k-dbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o12k-dbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sail" /></template>
