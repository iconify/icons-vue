<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt9uezbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9uezbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-outcome" /></template>
