<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m402nibjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m402nibjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medialyze-light" /></template>
