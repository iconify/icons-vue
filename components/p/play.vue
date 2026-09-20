<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyt0_tamv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyt0_tamv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:play" /></template>
