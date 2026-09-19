<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w20loqs-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w20loqs-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:volume-off" /></template>
