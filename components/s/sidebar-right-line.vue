<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aweq1wx_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aweq1wx_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-right-line" /></template>
