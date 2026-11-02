<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6py-uhso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6py-uhso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:package-2-line" /></template>
