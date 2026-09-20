<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv68w0biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv68w0biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:setting" /></template>
