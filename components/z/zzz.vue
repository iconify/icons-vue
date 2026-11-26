<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiok80bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qiok80bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:zzz" /></template>
