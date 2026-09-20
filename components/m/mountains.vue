<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbdd10buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbdd10buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:mountains" /></template>
