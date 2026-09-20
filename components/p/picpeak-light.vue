<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igxlhbcep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igxlhbcep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picpeak-light" /></template>
