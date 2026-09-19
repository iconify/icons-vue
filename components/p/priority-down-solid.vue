<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd632acsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd632acsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:priority-down-solid" /></template>
