<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi9plccts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi9plccts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xbackbone-light" /></template>
