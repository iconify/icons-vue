<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whks4rb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whks4rb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-heart" /></template>
