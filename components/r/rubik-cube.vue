<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfwvdk0fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfwvdk0fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rubik-cube" /></template>
