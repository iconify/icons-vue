<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch-7dkbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ch-7dkbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pixiv" /></template>
