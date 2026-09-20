<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmmzbdc6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmmzbdc6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openfga-light" /></template>
