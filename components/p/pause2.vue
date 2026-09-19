<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rajmr_bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rajmr_bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:pause2" /></template>
