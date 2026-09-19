<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0_n5sdns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":336,"height":496};
const content = `<path class="s0_n5sdns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:remote-control" /></template>
