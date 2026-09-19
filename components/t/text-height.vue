<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wojym8bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wojym8bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:text-height" /></template>
