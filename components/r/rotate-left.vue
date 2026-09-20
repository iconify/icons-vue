<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivrto5utr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ivrto5utr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:rotate-left" /></template>
