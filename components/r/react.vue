<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcm0_su8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcm0_su8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:react" /></template>
