<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w83t9bbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w83t9bbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:whale" /></template>
