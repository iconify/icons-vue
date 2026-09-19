<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wms074r1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":614};
const content = `<path class="wms074r1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:up" /></template>
