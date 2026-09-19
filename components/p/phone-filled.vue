<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlgo0vuug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlgo0vuug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-filled" /></template>
