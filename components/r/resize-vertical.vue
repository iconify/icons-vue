<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdhjl3ltj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zdhjl3ltj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:resize-vertical" /></template>
