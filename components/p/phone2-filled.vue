<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt05jtbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt05jtbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone2-filled" /></template>
