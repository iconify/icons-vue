<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pubj3xbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pubj3xbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sound-module-fill" /></template>
