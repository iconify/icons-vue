<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uihm9n3lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uihm9n3lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-close-bold" /></template>
