<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsaax2ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsaax2ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:phone-outgoing-line" /></template>
