<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avg0p0xjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avg0p0xjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:move-up-right" /></template>
