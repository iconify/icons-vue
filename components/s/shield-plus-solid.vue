<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftxpljb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftxpljb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-plus-solid" /></template>
