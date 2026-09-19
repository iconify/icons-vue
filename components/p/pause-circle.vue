<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhlzq_blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhlzq_blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pause-circle" /></template>
