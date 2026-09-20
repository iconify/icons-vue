<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcb_4fb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcb_4fb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:newsbreak" /></template>
