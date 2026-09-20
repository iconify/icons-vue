<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls8nwe1ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls8nwe1ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tag-plus-solid" /></template>
