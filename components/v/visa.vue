<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaw5iyi7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaw5iyi7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:visa" /></template>
