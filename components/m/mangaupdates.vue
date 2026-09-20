<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9y-2__bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9y-2__bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mangaupdates" /></template>
