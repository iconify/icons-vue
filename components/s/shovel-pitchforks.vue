<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifahunbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifahunbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shovel-pitchforks" /></template>
