<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfnd5x6bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfnd5x6bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vison-pro-fill" /></template>
