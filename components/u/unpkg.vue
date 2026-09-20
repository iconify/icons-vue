<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo4a6jivs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo4a6jivs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:unpkg" /></template>
