<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya863lksw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya863lksw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitter-logo-2" /></template>
