<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc6dvcb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xc6dvcb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trend-sideways" /></template>
