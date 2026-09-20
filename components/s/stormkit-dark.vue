<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyn4elw9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iyn4elw9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stormkit-dark" /></template>
