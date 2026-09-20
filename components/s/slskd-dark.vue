<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkcr4nuis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkcr4nuis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slskd-dark" /></template>
