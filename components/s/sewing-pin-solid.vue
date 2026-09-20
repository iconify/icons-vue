<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfylbybhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yfylbybhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:sewing-pin-solid" /></template>
