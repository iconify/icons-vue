<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlg_-wbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlg_-wbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:restaurant-menu" /></template>
