<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-jmyp62r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-jmyp62r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-10-fill" /></template>
