<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj1ucjb-u.css';
import '../../css/i/ixx-con_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tj1ucjb-u"/><path class="ixx-con_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-public" /></template>
