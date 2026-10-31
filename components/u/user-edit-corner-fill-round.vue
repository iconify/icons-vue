<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibyn8xbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibyn8xbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-edit-corner-fill-round" /></template>
