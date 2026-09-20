<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeap2tbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aeap2tbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splunk" /></template>
