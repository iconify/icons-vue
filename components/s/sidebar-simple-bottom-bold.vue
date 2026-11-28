<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut3vv_b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ut3vv_b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-bottom-bold" /></template>
