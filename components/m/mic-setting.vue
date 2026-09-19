<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2qqo_bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":496};
const content = `<path class="r2qqo_bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mic-setting" /></template>
