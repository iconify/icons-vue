<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-a0dacre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-a0dacre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:replane-dark" /></template>
