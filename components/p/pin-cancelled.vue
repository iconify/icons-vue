<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeoy3pben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yeoy3pben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pin-cancelled" /></template>
