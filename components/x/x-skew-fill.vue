<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umhfb7-2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="umhfb7-2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:x-skew-fill" /></template>
