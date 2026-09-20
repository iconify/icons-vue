<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4mbwbc9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4mbwbc9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volume-fill" /></template>
