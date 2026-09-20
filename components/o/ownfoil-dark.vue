<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4nbygbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m4nbygbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ownfoil-dark" /></template>
