<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03lv_xgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s03lv_xgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:playlist-plus" /></template>
