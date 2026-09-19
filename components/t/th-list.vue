<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nch_dfbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nch_dfbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:th-list" /></template>
