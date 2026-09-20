<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgrym0icu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgrym0icu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shower-head" /></template>
