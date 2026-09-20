<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd4roqayf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd4roqayf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-line" /></template>
