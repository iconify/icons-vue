<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm935zban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm935zban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-up-line" /></template>
