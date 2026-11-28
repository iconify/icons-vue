<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2h87kb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2h87kb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tram-clock" /></template>
