<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axftgxx0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1664};
const content = `<path class="axftgxx0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:twitch" /></template>
