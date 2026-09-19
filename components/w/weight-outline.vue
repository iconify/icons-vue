<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz5jy1b0j.css';
import '../../css/p/pcxysz9ao.css';
import '../../css/v/vwld5md-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz5jy1b0j"/><path class="pcxysz9ao"/><path clip-rule="evenodd" class="vwld5md-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:weight-outline" /></template>
