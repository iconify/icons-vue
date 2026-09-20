<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_i_1ouv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gf_i_1ouv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:timetagger-light" /></template>
