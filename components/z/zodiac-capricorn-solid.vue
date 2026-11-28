<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k51l8bchk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k51l8bchk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-capricorn-solid" /></template>
