<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd03o8bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd03o8bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:prompt-check" /></template>
