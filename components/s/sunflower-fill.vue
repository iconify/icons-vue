<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tar_hac0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tar_hac0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunflower-fill" /></template>
