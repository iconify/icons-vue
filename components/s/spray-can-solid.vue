<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzuua4itw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzuua4itw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spray-can-solid" /></template>
