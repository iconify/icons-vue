<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu3j08bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xu3j08bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spinnerr-dark" /></template>
