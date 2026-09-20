<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sluqg8b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sluqg8b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:safe" /></template>
