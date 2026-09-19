<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9v195bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9v195bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:refresh-ccw-filled" /></template>
