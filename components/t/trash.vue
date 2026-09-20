<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8i48bcjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8i48bcjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:trash" /></template>
