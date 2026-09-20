<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnd-ksbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnd-ksbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:math-solid" /></template>
