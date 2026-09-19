<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilbzs25se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilbzs25se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:scanning" /></template>
