<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_t-fpb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_t-fpb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:technitium-dark" /></template>
