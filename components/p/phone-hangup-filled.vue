<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu-816yyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu-816yyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-hangup-filled" /></template>
