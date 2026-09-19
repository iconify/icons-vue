<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8qq5rbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8qq5rbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone" /></template>
