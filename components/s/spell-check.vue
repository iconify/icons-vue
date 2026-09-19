<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kszy74b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kszy74b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:spell-check" /></template>
