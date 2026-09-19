<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvryw38cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvryw38cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pizza-slice" /></template>
