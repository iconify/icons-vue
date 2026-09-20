<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djpos4bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djpos4bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roon" /></template>
