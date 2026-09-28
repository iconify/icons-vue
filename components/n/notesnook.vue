<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxojr_bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxojr_bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:notesnook" /></template>
