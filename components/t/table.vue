<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax1jtlbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax1jtlbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:table" /></template>
