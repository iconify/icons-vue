<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_xpt-d8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b_xpt-d8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:piggybank" /></template>
