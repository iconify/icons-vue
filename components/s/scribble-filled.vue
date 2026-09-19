<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss9cfbbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss9cfbbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scribble-filled" /></template>
