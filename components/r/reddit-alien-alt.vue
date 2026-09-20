<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crho0cbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crho0cbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:reddit-alien-alt" /></template>
