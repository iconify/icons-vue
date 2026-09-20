<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcupe_3ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcupe_3ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:replay-10-fill" /></template>
