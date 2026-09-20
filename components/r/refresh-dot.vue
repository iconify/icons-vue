<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7-7o-bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-7o-bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:refresh-dot" /></template>
