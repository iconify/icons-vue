<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g96-5v8lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g96-5v8lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-round-square-bold" /></template>
