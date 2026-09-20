<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukh7dc-hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukh7dc-hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitter" /></template>
