<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6vok5b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6vok5b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-vertical-fill" /></template>
