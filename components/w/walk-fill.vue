<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfxlig6jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxlig6jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:walk-fill" /></template>
