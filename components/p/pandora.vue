<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut__hv4nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ut__hv4nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:pandora" /></template>
