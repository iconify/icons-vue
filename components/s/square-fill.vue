<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvim2ibiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvim2ibiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-fill" /></template>
