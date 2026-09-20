<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9c036b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9c036b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shlink-dark" /></template>
