<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgh016b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgh016b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nodl" /></template>
