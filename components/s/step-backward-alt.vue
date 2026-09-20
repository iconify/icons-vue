<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxb4yw5qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxb4yw5qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:step-backward-alt" /></template>
