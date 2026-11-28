<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei0zwbb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei0zwbb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:podcast-heart" /></template>
