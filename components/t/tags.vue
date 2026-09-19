<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaeh1toxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zaeh1toxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:tags" /></template>
