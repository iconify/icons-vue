<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v750lsb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v750lsb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spray-paint-can-with-spray" /></template>
