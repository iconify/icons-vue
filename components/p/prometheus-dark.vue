<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc1qq-8ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nc1qq-8ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prometheus-dark" /></template>
