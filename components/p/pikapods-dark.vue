<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f__75lbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f__75lbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pikapods-dark" /></template>
