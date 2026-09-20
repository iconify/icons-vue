<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz9_agbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oz9_agbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket" /></template>
