<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaimmzbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qaimmzbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stairs-duotone" /></template>
