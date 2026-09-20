<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk4ea3bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yk4ea3bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openaudible-dark" /></template>
