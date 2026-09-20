<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4br_ebme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4br_ebme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-2-fill" /></template>
