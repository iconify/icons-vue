<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s79mdyxni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s79mdyxni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-8-solid" /></template>
