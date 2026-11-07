<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqwv9fbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqwv9fbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-outline" /></template>
