<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed67yt6ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed67yt6ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sitepoint" /></template>
