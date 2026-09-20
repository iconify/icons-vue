<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6i7xsbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6i7xsbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openproject" /></template>
