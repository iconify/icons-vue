<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeh33x6-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeh33x6-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:maximize" /></template>
