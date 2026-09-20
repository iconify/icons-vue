<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnx2eibah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rnx2eibah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pulse" /></template>
