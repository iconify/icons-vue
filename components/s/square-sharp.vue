<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmleipb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmleipb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-sharp" /></template>
