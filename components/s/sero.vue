<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-m-zbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8-m-zbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sero" /></template>
