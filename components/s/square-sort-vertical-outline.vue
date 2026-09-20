<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai1gpwbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai1gpwbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-sort-vertical-outline" /></template>
