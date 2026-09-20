<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp13c28wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sp13c28wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-text" /></template>
