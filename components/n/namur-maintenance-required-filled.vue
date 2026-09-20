<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj_lodboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj_lodboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:namur-maintenance-required-filled" /></template>
