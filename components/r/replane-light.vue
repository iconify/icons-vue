<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oga4-ybii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oga4-ybii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:replane-light" /></template>
