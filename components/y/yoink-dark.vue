<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spsqxibps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spsqxibps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yoink-dark" /></template>
