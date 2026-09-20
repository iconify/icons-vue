<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wahrk07ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wahrk07ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:sim-off" /></template>
