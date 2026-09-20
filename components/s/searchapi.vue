<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkdk21fyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkdk21fyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:searchapi" /></template>
