<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syir6n91y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="syir6n91y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-outline" /></template>
