<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0d80ubpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0d80ubpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vernemq-dark" /></template>
