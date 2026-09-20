<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi60kxhue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi60kxhue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-xxxl" /></template>
