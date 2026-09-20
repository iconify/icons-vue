<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5utvzbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5utvzbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thrifty-dark" /></template>
