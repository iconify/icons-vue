<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5l_xac5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5l_xac5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:spond" /></template>
