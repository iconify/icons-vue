<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc-w-0b1k.css';
import '../../css/r/rihw2qt5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-w-0b1k"/><path class="rihw2qt5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:traffic-lights-line" /></template>
