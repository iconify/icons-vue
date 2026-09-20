<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3w34bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qe3w34bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paymenter-light" /></template>
