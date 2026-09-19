<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxlkmqbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":881};
const content = `<path class="sxlkmqbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:y" /></template>
