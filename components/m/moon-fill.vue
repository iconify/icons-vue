<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7xa7nbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7xa7nbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:moon-fill" /></template>
