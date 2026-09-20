<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iijq8npej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iijq8npej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:origamivault-dark" /></template>
