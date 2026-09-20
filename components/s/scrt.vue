<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy2y370gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy2y370gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:scrt" /></template>
