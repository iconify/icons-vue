<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivn4hmzox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivn4hmzox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ox" /></template>
