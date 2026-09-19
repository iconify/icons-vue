<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj6it4upb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xj6it4upb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:panel-expansion" /></template>
