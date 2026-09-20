<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_9lkzh9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_9lkzh9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slash-dark" /></template>
