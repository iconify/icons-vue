<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhe79hh6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhe79hh6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:right" /></template>
