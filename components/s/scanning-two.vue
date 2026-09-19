<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it71s2bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="it71s2bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:scanning-two" /></template>
