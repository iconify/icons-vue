<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m65l5mb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m65l5mb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stop-circle-bold" /></template>
