<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqh7--bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bqh7--bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2013-light" /></template>
