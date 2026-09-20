<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6f4tmb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6f4tmb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box-lock-open-outline" /></template>
