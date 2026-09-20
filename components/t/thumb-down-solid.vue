<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3epd7bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i3epd7bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:thumb-down-solid" /></template>
