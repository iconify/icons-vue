<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf-i5z3nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf-i5z3nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stream-bold" /></template>
