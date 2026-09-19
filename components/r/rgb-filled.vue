<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taih8t-2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taih8t-2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rgb-filled" /></template>
