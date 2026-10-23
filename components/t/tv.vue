<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pon66nbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pon66nbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tv" /></template>
