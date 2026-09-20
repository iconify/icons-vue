<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbhx6rimm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbhx6rimm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visual-db-dark" /></template>
