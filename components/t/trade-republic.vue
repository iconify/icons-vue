<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpyrxwlxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpyrxwlxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trade-republic" /></template>
