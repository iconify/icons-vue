<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-s44ccsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-s44ccsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:navigate-fill" /></template>
