<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh6v7rbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vh6v7rbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netlify-light" /></template>
