<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsgv3fble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsgv3fble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map-marker-edit" /></template>
