<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ja_s0el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g7ja_s0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sort-amount-asc" /></template>
