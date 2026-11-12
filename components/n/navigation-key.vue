<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw8moebdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw8moebdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-key" /></template>
