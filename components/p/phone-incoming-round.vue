<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix5wi_6hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix5wi_6hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-incoming-round" /></template>
