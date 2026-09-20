<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_7g23j3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_7g23j3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-8-fill" /></template>
