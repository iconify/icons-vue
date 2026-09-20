<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3bsu1bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3bsu1bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:qubes-os" /></template>
