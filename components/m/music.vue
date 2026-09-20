<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk4qabbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk4qabbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:music" /></template>
