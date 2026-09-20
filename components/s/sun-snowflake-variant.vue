<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u25cw5bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u25cw5bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sun-snowflake-variant" /></template>
