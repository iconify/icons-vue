<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4c8_ykb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cf4c8_ykb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-kubewarden-dark" /></template>
