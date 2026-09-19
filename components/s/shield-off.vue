<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz3o719wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz3o719wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:shield-off" /></template>
