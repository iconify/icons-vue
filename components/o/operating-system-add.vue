<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk_05bafr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pk_05bafr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:operating-system-add" /></template>
