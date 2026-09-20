<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0j4ft7bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0j4ft7bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-fill" /></template>
