<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnabqxbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hnabqxbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spliit-light" /></template>
