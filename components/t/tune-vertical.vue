<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru19-jbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru19-jbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tune-vertical" /></template>
