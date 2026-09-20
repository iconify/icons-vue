<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcuu03o1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcuu03o1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smore-newsletter-dark" /></template>
