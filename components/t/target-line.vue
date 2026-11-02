<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxy6v3jpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxy6v3jpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:target-line" /></template>
