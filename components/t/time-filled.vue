<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frg81opju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frg81opju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:time-filled" /></template>
