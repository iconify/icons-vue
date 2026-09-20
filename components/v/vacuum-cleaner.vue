<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rygkx9byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rygkx9byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vacuum-cleaner" /></template>
