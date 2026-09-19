<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1319_4lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1319_4lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-quote" /></template>
