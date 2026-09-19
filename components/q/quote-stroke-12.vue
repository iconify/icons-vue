<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9_ht237o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y9_ht237o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:quote-stroke-12" /></template>
