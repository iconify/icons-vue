<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj_no0yup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pj_no0yup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:western-digital-light" /></template>
