<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2zip_bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n2zip_bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshcore-dark" /></template>
