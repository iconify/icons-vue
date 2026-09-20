<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0wyz3bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0wyz3bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-follow-line" /></template>
