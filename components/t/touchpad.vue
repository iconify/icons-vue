<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4b7nactb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4b7nactb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:touchpad" /></template>
