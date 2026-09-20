<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gumdym6bg.css';
import '../../css/u/utf3i9a_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gumdym6bg"/><path class="utf3i9a_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:receipt" /></template>
