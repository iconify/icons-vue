<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evc_qlbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evc_qlbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:user-2" /></template>
