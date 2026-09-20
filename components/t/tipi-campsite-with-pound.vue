<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh9kv6vns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yh9kv6vns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsite-with-pound" /></template>
