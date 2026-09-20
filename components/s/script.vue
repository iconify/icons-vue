<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwhvnw36m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwhvnw36m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:script" /></template>
