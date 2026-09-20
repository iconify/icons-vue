<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr2hq2bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2hq2bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:stop-expressive" /></template>
