<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-x3u3ltf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-x3u3ltf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-heart-sharp" /></template>
