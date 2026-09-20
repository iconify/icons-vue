<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkck6lb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkck6lb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:zoom-in" /></template>
