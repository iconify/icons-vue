<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eacvhub6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eacvhub6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mail" /></template>
