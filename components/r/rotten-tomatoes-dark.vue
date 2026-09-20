<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybks5f9jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ybks5f9jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rotten-tomatoes-dark" /></template>
