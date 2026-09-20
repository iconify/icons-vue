<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z190gry6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z190gry6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:uber" /></template>
