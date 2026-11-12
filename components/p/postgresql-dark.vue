<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdnzp_0zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdnzp_0zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postgresql-dark" /></template>
