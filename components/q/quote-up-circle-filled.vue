<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-t85g_vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-t85g_vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:quote-up-circle-filled" /></template>
