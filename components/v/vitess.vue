<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dchv7qbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dchv7qbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vitess" /></template>
