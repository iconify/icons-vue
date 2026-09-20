<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy5mmc92w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy5mmc92w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt5" /></template>
