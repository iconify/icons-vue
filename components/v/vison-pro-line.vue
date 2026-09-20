<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gchj467ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gchj467ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vison-pro-line" /></template>
