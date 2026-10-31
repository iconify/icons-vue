<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9so2wdev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9so2wdev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-minus-corner-round" /></template>
