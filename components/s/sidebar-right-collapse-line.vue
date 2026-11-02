<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t71lnfbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t71lnfbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-right-collapse-line" /></template>
