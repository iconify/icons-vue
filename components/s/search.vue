<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haieeyb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="haieeyb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:search" /></template>
