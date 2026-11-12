<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe2kmybrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe2kmybrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pg-back-web-dark" /></template>
