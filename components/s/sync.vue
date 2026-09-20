<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsd7r4b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsd7r4b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sync" /></template>
