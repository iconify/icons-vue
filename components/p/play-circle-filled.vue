<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua3yv8b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua3yv8b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:play-circle-filled" /></template>
