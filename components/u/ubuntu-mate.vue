<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynwtrqblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynwtrqblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ubuntu-mate" /></template>
