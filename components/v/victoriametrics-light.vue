<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh157dkwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gh157dkwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:victoriametrics-light" /></template>
