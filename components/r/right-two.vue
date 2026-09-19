<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r360sfbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r360sfbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:right-two" /></template>
