<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_new4w6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_new4w6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:signal-solid" /></template>
