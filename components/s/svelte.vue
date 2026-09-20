<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onm3z34ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onm3z34ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:svelte" /></template>
