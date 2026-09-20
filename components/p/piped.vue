<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icxhp86hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icxhp86hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:piped" /></template>
