<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my_cuacnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my_cuacnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left" /></template>
