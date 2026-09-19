<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyzybgk3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyzybgk3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:thunderstorm-strong-filled" /></template>
