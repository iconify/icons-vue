<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgr19of2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgr19of2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rectangle-fill" /></template>
