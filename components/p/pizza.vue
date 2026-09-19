<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuzej1iwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="xuzej1iwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pizza" /></template>
