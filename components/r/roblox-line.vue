<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlzpevisc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlzpevisc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:roblox-line" /></template>
