<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6_-33bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g6_-33bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:runtipi-light" /></template>
