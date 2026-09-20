<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5exlyb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5exlyb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-half" /></template>
