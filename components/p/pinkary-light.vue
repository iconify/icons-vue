<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu4567t3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iu4567t3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinkary-light" /></template>
