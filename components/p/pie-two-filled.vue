<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7i2tnc_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d7i2tnc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pie-two-filled" /></template>
