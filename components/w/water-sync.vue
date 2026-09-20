<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cisfx-aim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cisfx-aim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:water-sync" /></template>
