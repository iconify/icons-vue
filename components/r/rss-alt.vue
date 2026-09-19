<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbgr5tblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="pbgr5tblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:rss-alt" /></template>
