<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw_qgvbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw_qgvbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-hospital" /></template>
