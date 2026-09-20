<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whfbv-bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whfbv-bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ripe-atlas-dark" /></template>
