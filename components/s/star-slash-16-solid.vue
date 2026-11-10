<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qheom710l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qheom710l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:star-slash-16-solid" /></template>
