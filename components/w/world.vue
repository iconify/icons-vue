<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8qs2k-uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8qs2k-uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:world" /></template>
