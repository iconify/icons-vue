<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq5np1vsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kq5np1vsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-circle-20-bold" /></template>
