<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgxa4cbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgxa4cbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signal-4g-plus" /></template>
