<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiw01h8mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiw01h8mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:scorecard" /></template>
