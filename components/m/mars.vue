<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb93p3fbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="vb93p3fbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mars" /></template>
