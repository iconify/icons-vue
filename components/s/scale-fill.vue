<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5vg0db_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5vg0db_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scale-fill" /></template>
