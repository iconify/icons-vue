<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd5pp1qjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd5pp1qjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neohabit-dark" /></template>
