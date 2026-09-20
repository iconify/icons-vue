<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-obghb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-obghb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:windows-line" /></template>
