<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh-i5vb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bh-i5vb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vitepress-dark" /></template>
