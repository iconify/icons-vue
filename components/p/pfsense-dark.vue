<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouab2__2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouab2__2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pfsense-dark" /></template>
