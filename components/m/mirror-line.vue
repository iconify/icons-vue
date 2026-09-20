<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-s6bkbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-s6bkbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mirror-line" /></template>
