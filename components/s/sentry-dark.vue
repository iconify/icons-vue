<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so6_o88bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="so6_o88bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sentry-dark" /></template>
