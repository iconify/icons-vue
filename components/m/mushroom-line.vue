<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx_6zbbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx_6zbbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mushroom-line" /></template>
