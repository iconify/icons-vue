<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6_q2dyiy.css';
import '../../css/q/q2inojbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6_q2dyiy"/><path class="q2inojbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storybook" /></template>
