<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b225b0bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b225b0bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:noton-light" /></template>
