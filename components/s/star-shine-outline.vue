<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us0-41abq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="us0-41abq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-shine-outline" /></template>
