<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpdeyibxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpdeyibxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:medium-line" /></template>
