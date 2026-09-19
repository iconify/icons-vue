<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubbkpfkka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubbkpfkka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:playlist-audio" /></template>
