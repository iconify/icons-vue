<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmlje1b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmlje1b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-7-fill" /></template>
