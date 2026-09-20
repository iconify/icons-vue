<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqx2n2bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqx2n2bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snappymail-dark" /></template>
