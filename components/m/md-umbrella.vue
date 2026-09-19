<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egg3vdbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="egg3vdbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-umbrella" /></template>
