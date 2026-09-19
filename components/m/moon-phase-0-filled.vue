<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y82uu8bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y82uu8bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-0-filled" /></template>
