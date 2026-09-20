<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv69e6bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv69e6bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plumio-light" /></template>
