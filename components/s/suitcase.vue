<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqgwv0bzt.css';
import '../../css/y/yi6ar83pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uqgwv0bzt"/><path class="yi6ar83pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:suitcase" /></template>
