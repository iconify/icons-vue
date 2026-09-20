<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw-wv0b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mw-wv0b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table" /></template>
