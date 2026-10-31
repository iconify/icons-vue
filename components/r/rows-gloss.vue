<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so-2c2wtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so-2c2wtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rows-gloss" /></template>
