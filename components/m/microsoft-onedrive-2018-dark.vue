<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt65rufct.css';
import '../../css/l/l_uk_bbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qt65rufct"/><path class="l_uk_bbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-2018-dark" /></template>
