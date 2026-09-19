<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1rjd1qxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1rjd1qxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:music-outline" /></template>
