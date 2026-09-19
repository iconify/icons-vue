<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2kk3caou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2kk3caou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:torii-gate" /></template>
