<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7s0spbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7s0spbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:previous2-filled" /></template>
