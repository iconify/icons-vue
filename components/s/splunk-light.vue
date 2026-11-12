<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tby322bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tby322bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splunk-light" /></template>
