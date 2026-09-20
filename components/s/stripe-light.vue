<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1tjpti_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1tjpti_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stripe-light" /></template>
