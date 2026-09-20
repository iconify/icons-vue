<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fepozmboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fepozmboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mumble" /></template>
