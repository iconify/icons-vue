<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p65yppbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p65yppbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mini-qr-light" /></template>
