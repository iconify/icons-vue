<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n66eg7bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n66eg7bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plug-gloss" /></template>
