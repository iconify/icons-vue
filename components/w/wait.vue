<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgyn5dtqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgyn5dtqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wait" /></template>
