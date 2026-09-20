<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oik3pl-qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oik3pl-qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plexamp-dark" /></template>
