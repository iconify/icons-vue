<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w30-36ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w30-36ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spinnerr-dark" /></template>
