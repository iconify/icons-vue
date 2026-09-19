<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgrlf-b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgrlf-b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mic-02" /></template>
