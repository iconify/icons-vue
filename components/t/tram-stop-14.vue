<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcwryob9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wcwryob9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:tram-stop-14" /></template>
