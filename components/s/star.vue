<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg5icdcma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bg5icdcma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:star" /></template>
