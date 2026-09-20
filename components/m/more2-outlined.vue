<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug4xqib1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug4xqib1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:more2-outlined" /></template>
