<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlkg52b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlkg52b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-2-bold" /></template>
