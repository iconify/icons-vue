<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuuvg9cpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuuvg9cpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:snow-flake" /></template>
