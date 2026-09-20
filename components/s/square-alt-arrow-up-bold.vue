<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttzitdboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttzitdboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-alt-arrow-up-bold" /></template>
