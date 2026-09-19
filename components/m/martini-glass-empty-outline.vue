<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-kjeqmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-kjeqmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:martini-glass-empty-outline" /></template>
