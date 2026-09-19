<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd-bllh8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fd-bllh8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-arrow-up" /></template>
