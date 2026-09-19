<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-dy-ubtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="v-dy-ubtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:survey" /></template>
