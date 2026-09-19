<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_4s_obaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_4s_obaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:spam" /></template>
