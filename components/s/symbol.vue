<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkdflzb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wkdflzb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:symbol" /></template>
