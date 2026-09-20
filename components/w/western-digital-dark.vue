<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh21_cckm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh21_cckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:western-digital-dark" /></template>
