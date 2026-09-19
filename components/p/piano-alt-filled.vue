<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fddobqp8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fddobqp8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piano-alt-filled" /></template>
