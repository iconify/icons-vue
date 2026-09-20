<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehdnanaqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ehdnanaqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailflow-sh-light" /></template>
