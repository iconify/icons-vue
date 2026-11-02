<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dszeum64l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dszeum64l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-left-open-line" /></template>
