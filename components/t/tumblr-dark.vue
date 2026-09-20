<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spirxobzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spirxobzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tumblr-dark" /></template>
