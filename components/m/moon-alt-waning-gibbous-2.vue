<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef-ovpf1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ef-ovpf1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-gibbous-2" /></template>
