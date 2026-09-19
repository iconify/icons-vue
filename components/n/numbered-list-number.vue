<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz-xk656g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tz-xk656g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:numbered-list-number" /></template>
