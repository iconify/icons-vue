<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjh0hj0uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2016,"height":1984};
const content = `<path class="wjh0hj0uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:panther" /></template>
