<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/polw2wtcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="polw2wtcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:section-fill" /></template>
