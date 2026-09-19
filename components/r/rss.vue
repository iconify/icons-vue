<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynmazaczn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ynmazaczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:rss" /></template>
