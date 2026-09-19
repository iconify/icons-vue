<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzcw81byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzcw81byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:type-outline" /></template>
