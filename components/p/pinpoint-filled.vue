<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny8bffbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ny8bffbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:pinpoint-filled" /></template>
