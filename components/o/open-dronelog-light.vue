<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuj184buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cuj184buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-dronelog-light" /></template>
