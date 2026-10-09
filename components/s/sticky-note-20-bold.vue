<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyer2sg9u.css';
import '../../css/w/w9octyb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tyer2sg9u"/><path class="w9octyb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticky-note-20-bold" /></template>
