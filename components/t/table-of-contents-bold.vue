<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw4v4jmms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rw4v4jmms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:table-of-contents-bold" /></template>
