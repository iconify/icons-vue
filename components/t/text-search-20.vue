<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmqzfdcfq.css';
import '../../css/m/mq74mlbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cmqzfdcfq"/><path class="mq74mlbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-search-20" /></template>
