<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apfc86bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="apfc86bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:spray-can" /></template>
