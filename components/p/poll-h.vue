<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbhfrjrke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rbhfrjrke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:poll-h" /></template>
