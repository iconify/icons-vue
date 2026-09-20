<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh-qmcohf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rh-qmcohf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sailboat" /></template>
