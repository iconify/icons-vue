<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nns_4vajp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nns_4vajp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-classical-building-with-dome-and-flag" /></template>
