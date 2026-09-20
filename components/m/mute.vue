<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubbqkn23c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubbqkn23c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:mute" /></template>
