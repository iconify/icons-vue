<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3oq4jbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3oq4jbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-circle-solid" /></template>
