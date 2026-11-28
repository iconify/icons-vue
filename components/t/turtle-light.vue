<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhp7iwb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fhp7iwb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:turtle-light" /></template>
