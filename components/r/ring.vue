<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqruxjb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqruxjb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ring" /></template>
