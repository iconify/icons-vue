<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1z6a0a3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m1z6a0a3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shuthost-light" /></template>
