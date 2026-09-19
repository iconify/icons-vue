<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izrtih2_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="izrtih2_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:minetest" /></template>
