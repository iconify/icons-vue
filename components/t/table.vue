<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fciy3kb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fciy3kb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:table" /></template>
