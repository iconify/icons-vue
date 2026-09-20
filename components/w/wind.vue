<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxjspdb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kxjspdb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wind" /></template>
