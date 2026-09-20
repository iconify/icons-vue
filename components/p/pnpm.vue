<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp65438ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp65438ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pnpm" /></template>
