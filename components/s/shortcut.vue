<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo937_3bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo937_3bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:shortcut" /></template>
