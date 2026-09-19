<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_iv796sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_iv796sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:telegram" /></template>
