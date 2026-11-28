<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdawh-2am.css';
import '../../css/d/dcxarjboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdawh-2am secondary"/><path class="dcxarjboh primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reply-arrow-duo" /></template>
