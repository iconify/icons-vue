<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv4wbxftm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pv4wbxftm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:switch-track" /></template>
