<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp-ka5bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp-ka5bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-left-line" /></template>
