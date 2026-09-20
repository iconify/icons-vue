<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8ye8b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tj8ye8b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:save-all" /></template>
