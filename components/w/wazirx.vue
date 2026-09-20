<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i75_g2pth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i75_g2pth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wazirx" /></template>
