<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i09v-mbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i09v-mbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:two-factor-authentication" /></template>
