<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u22te8bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u22te8bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnipoly" /></template>
