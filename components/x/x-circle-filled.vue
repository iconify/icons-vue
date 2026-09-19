<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-89rbqjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-89rbqjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:x-circle-filled" /></template>
