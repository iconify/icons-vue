<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-4cpzbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l-4cpzbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-shinto-15" /></template>
