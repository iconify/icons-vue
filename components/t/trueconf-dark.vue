<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4jb__b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c4jb__b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trueconf-dark" /></template>
