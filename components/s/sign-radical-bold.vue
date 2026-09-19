<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3el61bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3el61bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-radical-bold" /></template>
