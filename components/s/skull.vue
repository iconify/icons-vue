<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5m6x7bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5m6x7bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:skull" /></template>
