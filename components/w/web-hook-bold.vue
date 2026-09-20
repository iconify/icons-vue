<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aom6z3bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aom6z3bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:web-hook-bold" /></template>
