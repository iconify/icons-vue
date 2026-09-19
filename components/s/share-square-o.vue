<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9wjtwlcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="e9wjtwlcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:share-square-o" /></template>
