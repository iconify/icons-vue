<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbu14lbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbu14lbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:retro-achievements" /></template>
