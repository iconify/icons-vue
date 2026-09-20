<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqxajmb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqxajmb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:x-twitter-logo" /></template>
