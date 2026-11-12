<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trhwvieil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trhwvieil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloudpi-dark" /></template>
