<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlal61btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlal61btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sidebar-expand-solid" /></template>
