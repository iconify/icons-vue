<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i51d29kag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i51d29kag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:users-info" /></template>
