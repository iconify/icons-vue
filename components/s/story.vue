<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjz9o4bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjz9o4bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:story" /></template>
