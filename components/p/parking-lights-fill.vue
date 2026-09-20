<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dshqe4b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dshqe4b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parking-lights-fill" /></template>
