<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw5145ocz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nw5145ocz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:paintbrush" /></template>
