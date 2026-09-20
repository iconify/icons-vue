<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_nk98b2c.css';
import '../../css/d/d9qn9ybwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_nk98b2c"/><path class="d9qn9ybwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vertigo-comics" /></template>
