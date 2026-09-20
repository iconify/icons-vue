<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj9nae0yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj9nae0yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:modem" /></template>
