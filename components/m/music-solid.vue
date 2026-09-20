<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-6smlkmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6smlkmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:music-solid" /></template>
