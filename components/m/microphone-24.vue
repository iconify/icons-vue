<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjas6y7nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjas6y7nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:microphone-24" /></template>
