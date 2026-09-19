<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y68fl5rto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="y68fl5rto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:paper-clip-alt" /></template>
