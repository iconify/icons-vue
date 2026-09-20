<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2qv74buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2qv74buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:reserve-filled" /></template>
