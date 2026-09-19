<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_6ob4nca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_6ob4nca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:star" /></template>
