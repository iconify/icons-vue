<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaf37bbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yaf37bbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sure-finance-dark" /></template>
