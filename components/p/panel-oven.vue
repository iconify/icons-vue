<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbon7ib7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbon7ib7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-oven" /></template>
