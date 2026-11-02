<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggim82b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggim82b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-fill" /></template>
