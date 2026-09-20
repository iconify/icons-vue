<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z413z9k6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z413z9k6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:marker-cancel" /></template>
