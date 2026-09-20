<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7znt3bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n7znt3bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:mathematics-display-block" /></template>
