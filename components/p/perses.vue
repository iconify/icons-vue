<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbosynb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vbosynb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perses" /></template>
