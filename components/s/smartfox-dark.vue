<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x96h1bhdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x96h1bhdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smartfox-dark" /></template>
