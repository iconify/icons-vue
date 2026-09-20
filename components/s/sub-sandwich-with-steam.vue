<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc9-v5b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yc9-v5b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sub-sandwich-with-steam" /></template>
