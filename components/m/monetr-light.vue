<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oycn88bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oycn88bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:monetr-light" /></template>
