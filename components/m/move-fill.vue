<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-155s8pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-155s8pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:move-fill" /></template>
