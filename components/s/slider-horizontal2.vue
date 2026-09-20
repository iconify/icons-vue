<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld5r8bbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld5r8bbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-horizontal2" /></template>
