<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrnmp8poh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrnmp8poh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-5-fill" /></template>
