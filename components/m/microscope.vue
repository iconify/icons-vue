<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx2ol4b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="dx2ol4b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:microscope" /></template>
