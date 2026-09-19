<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbd350alm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lbd350alm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicatorf" /></template>
