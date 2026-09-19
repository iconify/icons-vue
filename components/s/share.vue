<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz0akj-mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yz0akj-mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:share" /></template>
