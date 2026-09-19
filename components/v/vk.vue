<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au417ft5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au417ft5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:vk" /></template>
