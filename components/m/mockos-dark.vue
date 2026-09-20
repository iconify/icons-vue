<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3361obte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j3361obte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mockos-dark" /></template>
