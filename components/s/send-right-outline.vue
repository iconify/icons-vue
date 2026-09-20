<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqddq8bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mqddq8bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-right-outline" /></template>
