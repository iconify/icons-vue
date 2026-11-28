<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpd-y_4wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpd-y_4wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-plus" /></template>
