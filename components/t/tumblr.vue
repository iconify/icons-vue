<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6q5rebuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6q5rebuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:tumblr" /></template>
