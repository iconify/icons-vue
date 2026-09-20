<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ad6t4cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ad6t4cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scrapbox" /></template>
