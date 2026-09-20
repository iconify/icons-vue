<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_6hk7b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_6hk7b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-1-fill" /></template>
