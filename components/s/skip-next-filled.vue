<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9gyv8bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9gyv8bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:skip-next-filled" /></template>
