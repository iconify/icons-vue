<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg0b1bc1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg0b1bc1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share" /></template>
