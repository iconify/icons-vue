<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mukfgmbez.css';
import '../../css/y/ynttdhfug.css';
import '../../css/p/p9bu9v51v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mukfgmbez"/><path class="ynttdhfug"/><path class="p9bu9v51v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mx" /></template>
