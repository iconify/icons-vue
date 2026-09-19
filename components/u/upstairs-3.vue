<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iknyyxzct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iknyyxzct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:upstairs-3" /></template>
