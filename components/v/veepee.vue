<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fguyq0bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fguyq0bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:veepee" /></template>
