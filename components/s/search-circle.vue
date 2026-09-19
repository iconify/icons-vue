<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo31ksc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fo31ksc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:search-circle" /></template>
