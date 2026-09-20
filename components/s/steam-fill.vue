<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs3209b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs3209b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:steam-fill" /></template>
