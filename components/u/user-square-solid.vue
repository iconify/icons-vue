<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h45fo5bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h45fo5bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-square-solid" /></template>
