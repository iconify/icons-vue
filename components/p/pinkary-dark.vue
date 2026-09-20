<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goz9-9kzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="goz9-9kzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinkary-dark" /></template>
