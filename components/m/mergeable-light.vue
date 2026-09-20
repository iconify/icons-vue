<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z00yxpbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z00yxpbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mergeable-light" /></template>
