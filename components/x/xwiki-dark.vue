<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni1alsbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni1alsbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xwiki-dark" /></template>
