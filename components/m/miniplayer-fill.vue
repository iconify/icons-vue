<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0gfe_3pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0gfe_3pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:miniplayer-fill" /></template>
