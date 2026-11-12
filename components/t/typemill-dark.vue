<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj3b2hoai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dj3b2hoai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typemill-dark" /></template>
