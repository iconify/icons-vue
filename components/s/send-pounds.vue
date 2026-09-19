<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hogky4pfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hogky4pfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:send-pounds" /></template>
