<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xltx7yb9x.css';
import '../../css/k/kogil-gfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xltx7yb9x"/><path class="kogil-gfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:network-search-bold" /></template>
