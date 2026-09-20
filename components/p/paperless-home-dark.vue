<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogoa_1oaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogoa_1oaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paperless-home-dark" /></template>
