<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w65hz1z2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w65hz1z2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pipe" /></template>
