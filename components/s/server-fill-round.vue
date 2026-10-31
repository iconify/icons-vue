<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5g-q6bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5g-q6bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-fill-round" /></template>
