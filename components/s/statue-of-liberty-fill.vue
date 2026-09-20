<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvs1ozbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvs1ozbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:statue-of-liberty-fill" /></template>
