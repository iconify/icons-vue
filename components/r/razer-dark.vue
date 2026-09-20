<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hugdy87ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hugdy87ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:razer-dark" /></template>
