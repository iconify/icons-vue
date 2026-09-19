<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/demkhgwzh.css';
import '../../css/t/to1_2obdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="demkhgwzh"/><path class="to1_2obdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stop-outline-filled" /></template>
