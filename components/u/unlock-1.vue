<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u24hh5b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u24hh5b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:unlock-1" /></template>
