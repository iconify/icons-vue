<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy-tkibau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cy-tkibau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stretching-round-outline" /></template>
