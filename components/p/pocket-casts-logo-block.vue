<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2g0yejfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2g0yejfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:pocket-casts-logo-block" /></template>
