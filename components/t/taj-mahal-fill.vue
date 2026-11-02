<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlwseac3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwseac3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:taj-mahal-fill" /></template>
