<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nofwodbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nofwodbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ruler-vertical-solid" /></template>
