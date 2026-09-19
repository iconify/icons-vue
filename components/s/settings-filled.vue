<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xesjvgb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xesjvgb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:settings-filled" /></template>
