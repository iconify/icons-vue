<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjqk-xdgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjqk-xdgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speak-ai-fill" /></template>
