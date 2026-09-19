<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1f4ofbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w1f4ofbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:right-two" /></template>
