<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-5ggzb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-5ggzb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:palantir" /></template>
