<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c86_q-b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c86_q-b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:move-right" /></template>
