<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg8ugcbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sg8ugcbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:right-two" /></template>
