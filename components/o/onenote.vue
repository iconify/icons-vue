<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85t0r4ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f85t0r4ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:onenote" /></template>
