<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qucs97x-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qucs97x-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:send-fill" /></template>
