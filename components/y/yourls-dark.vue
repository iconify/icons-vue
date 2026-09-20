<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emhy2jo_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="emhy2jo_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yourls-dark" /></template>
