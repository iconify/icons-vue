<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vucvnjbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vucvnjbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pswap" /></template>
