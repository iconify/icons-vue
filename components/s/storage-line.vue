<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_ez1ac2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_ez1ac2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:storage-line" /></template>
