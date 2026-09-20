<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx6hg60hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nx6hg60hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:scuba-diving" /></template>
