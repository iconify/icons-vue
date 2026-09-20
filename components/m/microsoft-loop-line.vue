<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzz8phbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzz8phbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:microsoft-loop-line" /></template>
