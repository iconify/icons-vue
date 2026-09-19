<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojuxshbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojuxshbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-03" /></template>
