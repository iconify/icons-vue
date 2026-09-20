<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwhzqxb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jwhzqxb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sign-in-squre-fill" /></template>
