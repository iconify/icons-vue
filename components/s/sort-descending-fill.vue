<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvfxyn91a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvfxyn91a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sort-descending-fill" /></template>
