<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tto8q_bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tto8q_bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings-dot-fill" /></template>
