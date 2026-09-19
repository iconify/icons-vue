<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv4q92b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pv4q92b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:star-empty" /></template>
