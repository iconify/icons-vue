<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xiqk_0v.css';
import '../../css/o/oo004ivrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4xiqk_0v"/><path class="oo004ivrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:toggle-left" /></template>
